<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tri1pdban.css';
import '../../css/r/r5hjnw2io.css';
import '../../css/f/f59hu7jtt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tri1pdban"/><path class="r5hjnw2io"/><path clip-rule="evenodd" class="f59hu7jtt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:align-top-bold-duotone" {...props}></Icon>
