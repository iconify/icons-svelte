<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxgjq0bfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oxgjq0bfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:paper-airplane" {...props}></Icon>
