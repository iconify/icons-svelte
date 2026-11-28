<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/glh30ik0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="glh30ik0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:credit-card" {...props}></Icon>
