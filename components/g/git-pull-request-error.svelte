<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kraedhl7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kraedhl7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:git-pull-request-error" {...props}></Icon>
