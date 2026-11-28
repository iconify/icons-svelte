<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czurdaczw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="czurdaczw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:panel-top-collapse-solid" {...props}></Icon>
