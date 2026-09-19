<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k42670bpw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="k42670bpw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:magnifier-plus" {...props}></Icon>
