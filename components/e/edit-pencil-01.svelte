<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1-_mvbyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x1-_mvbyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:edit-pencil-01" {...props}></Icon>
