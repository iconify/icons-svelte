<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/huvje1kqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="huvje1kqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:heading-h1" {...props}></Icon>
