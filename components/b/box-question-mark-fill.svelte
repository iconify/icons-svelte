<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a22dcsy8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a22dcsy8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:box-question-mark-fill" {...props}></Icon>
