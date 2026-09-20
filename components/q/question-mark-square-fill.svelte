<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6uc1hb5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d6uc1hb5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:question-mark-square-fill" {...props}></Icon>
