<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jui78c6qa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jui78c6qa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:chevron-left-circle-fill" {...props}></Icon>
