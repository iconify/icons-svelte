<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/apc9u9b0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="apc9u9b0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:form-view" {...props}></Icon>
