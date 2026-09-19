<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/du9039guc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="du9039guc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:pinterest" {...props}></Icon>
