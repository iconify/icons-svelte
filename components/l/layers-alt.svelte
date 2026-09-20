<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jh21ckg-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jh21ckg-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:layers-alt" {...props}></Icon>
