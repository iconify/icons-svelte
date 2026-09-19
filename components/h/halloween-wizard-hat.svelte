<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohz0agb6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ohz0agb6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:halloween-wizard-hat" {...props}></Icon>
