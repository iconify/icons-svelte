<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vjl46-bna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vjl46-bna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:more-vert-fill" {...props}></Icon>
