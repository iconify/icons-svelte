<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d56dqs-ms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="d56dqs-ms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:ecology-science-erlenmeyer-flask-experiment-lab-flask-science-chemistry-solution" {...props}></Icon>
