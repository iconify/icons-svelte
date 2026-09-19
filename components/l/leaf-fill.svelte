<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/br4hz9-6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="br4hz9-6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:leaf-fill" {...props}></Icon>
