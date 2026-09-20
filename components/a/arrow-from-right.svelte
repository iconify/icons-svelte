<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/brrbztb-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="brrbztb-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:arrow-from-right" {...props}></Icon>
