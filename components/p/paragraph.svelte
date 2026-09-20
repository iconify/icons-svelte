<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eg0i-6tnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eg0i-6tnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:paragraph" {...props}></Icon>
