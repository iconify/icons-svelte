<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbluk9b-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bbluk9b-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:arrow-up-right-square-fill" {...props}></Icon>
