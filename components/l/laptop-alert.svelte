<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/di89s5fjs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="di89s5fjs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:laptop-alert" {...props}></Icon>
