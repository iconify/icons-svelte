<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pep7mub8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pep7mub8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:briefcase-fill" {...props}></Icon>
