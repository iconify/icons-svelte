<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a8d99nb6o.css';
import '../../css/u/ur2d1ktml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a8d99nb6o"/><path class="ur2d1ktml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:cog" {...props}></Icon>
