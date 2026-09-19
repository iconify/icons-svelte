<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iaj7ns9kj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="iaj7ns9kj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:angry" {...props}></Icon>
