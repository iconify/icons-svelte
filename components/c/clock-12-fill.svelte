<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzg4uzwts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tzg4uzwts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:clock-12-fill" {...props}></Icon>
