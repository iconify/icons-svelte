<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cybge4bnp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="cybge4bnp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:briefcase-alt-solid" {...props}></Icon>
