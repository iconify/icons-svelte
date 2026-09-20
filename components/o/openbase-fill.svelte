<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ge-w7b-ez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ge-w7b-ez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:openbase-fill" {...props}></Icon>
