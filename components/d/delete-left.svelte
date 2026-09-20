<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yyed1cbvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yyed1cbvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:delete-left" {...props}></Icon>
