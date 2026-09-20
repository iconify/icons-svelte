<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/a/a3y69p.css';
import '../../css/c/cquv0f.css';
import '../../css/s/so-from-26.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c a3y69p"/><path class="a0m25c cquv0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:navigation-right-up" {...props}></Icon>
