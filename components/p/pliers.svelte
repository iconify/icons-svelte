<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vee8of9rb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vee8of9rb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:pliers" {...props}></Icon>
