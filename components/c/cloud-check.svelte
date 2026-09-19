<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kk1b1pbeh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="kk1b1pbeh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:cloud-check" {...props}></Icon>
