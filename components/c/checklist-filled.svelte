<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vi_ta4byr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vi_ta4byr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:checklist-filled" {...props}></Icon>
