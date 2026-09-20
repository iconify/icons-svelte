<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezau3nrei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ezau3nrei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:alien-filled" {...props}></Icon>
