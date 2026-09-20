<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ea74s5vdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ea74s5vdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:account-edit" {...props}></Icon>
