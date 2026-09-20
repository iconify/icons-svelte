<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fr3g4wqkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fr3g4wqkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:bag-dollar-solid" {...props}></Icon>
