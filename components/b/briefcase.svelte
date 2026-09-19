<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k70tccb4z.css';
import '../../css/j/jhd2mpbdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k70tccb4z"/><path class="jhd2mpbdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:briefcase" {...props}></Icon>
