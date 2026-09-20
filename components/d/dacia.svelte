<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ghzaz6bud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ghzaz6bud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:dacia" {...props}></Icon>
