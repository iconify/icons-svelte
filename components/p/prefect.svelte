<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6wnk9bar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b6wnk9bar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:prefect" {...props}></Icon>
