<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ssq8clb7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ssq8clb7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:account-alert" {...props}></Icon>
