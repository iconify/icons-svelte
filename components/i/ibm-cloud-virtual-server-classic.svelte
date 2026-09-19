<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzccu8bfu.css';
import '../../css/o/om3uz4b8p.css';
import '../../css/c/csyesnsto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="jzccu8bfu"/><path class="om3uz4b8p"/><path class="csyesnsto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-cloud-virtual-server-classic" {...props}></Icon>
