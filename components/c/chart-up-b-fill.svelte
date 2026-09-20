<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fgrfvbb6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fgrfvbb6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:chart-up-b-fill" {...props}></Icon>
