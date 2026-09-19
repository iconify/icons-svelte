<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/juq_70b2e.css';
import '../../css/b/b48fucctu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="juq_70b2e"/><path class="b48fucctu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-up-on-square-stack-16-solid" {...props}></Icon>
