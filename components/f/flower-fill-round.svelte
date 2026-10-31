<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gqgebmbjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gqgebmbjw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:flower-fill-round" {...props}></Icon>
