<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lvg8s9_1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lvg8s9_1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:form-trash" {...props}></Icon>
