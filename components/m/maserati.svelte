<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nsjiht7-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nsjiht7-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:maserati" {...props}></Icon>
