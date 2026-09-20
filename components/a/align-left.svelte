<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6xus7bkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h6xus7bkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:align-left" {...props}></Icon>
