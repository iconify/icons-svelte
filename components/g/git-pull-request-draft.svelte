<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m10uqxfeb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m10uqxfeb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:git-pull-request-draft" {...props}></Icon>
