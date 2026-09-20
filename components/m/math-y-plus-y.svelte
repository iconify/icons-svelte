<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uggdc9ofk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uggdc9ofk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:math-y-plus-y" {...props}></Icon>
