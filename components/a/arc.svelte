<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ejz479zpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ejz479zpm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:arc" {...props}></Icon>
