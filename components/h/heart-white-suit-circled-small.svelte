<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jd2i4dbpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="jd2i4dbpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:heart-white-suit-circled-small" {...props}></Icon>
