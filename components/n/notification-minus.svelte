<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u9pm7ackg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u9pm7ackg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:notification-minus" {...props}></Icon>
