<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2vjnjw9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="q2vjnjw9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-snowboarding-downhill" {...props}></Icon>
