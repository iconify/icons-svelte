<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pizheebef.css';
import '../../css/u/ui_93yeww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pizheebef"/><path class="ui_93yeww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:play-bold-duotone" {...props}></Icon>
