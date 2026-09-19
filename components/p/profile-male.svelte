<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ab5784bmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":32};
const content = `<path class="ab5784bmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="et:profile-male" {...props}></Icon>
