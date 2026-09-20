<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qu1ht9fgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qu1ht9fgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:external-link-solid" {...props}></Icon>
