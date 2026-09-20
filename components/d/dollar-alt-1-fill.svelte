<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bsgld8g3i.css';
import '../../css/t/tehcrdk0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bsgld8g3i"/><path clip-rule="evenodd" class="tehcrdk0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:dollar-alt-1-fill" {...props}></Icon>
