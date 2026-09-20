<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qt_dw-i0g.css';
import '../../css/t/t824cqbjs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qt_dw-i0g"/><path clip-rule="evenodd" class="t824cqbjs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:ai-shield-fill" {...props}></Icon>
