<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b9cqm39fx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="b9cqm39fx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:reservoir-20-bold" {...props}></Icon>
