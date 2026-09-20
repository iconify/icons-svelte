<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xyoyyqbeu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xyoyyqbeu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:credit-card-2-fill" {...props}></Icon>
