<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o726blbnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o726blbnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:github-sponsors" {...props}></Icon>
