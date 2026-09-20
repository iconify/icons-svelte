<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zwus2bcyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zwus2bcyf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:numeric-eight-box-multiple-outline" {...props}></Icon>
