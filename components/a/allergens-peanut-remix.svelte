<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w3kxiz0zt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w3kxiz0zt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:allergens-peanut-remix" {...props}></Icon>
