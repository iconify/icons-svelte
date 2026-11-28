<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsyie6gxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dsyie6gxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:point-up-solid" {...props}></Icon>
