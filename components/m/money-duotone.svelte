<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/a21mw4alh.css';
import '../../css/k/kor5vl3yu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="a21mw4alh"/><path class="kor5vl3yu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:money-duotone" {...props}></Icon>
