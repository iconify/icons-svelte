<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drpgpy39b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="drpgpy39b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:list-numbers-bold" {...props}></Icon>
