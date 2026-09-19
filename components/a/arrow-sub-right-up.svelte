<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c--5i5fyl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c--5i5fyl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:arrow-sub-right-up" {...props}></Icon>
