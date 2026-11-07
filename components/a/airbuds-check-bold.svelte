<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cg7x8js6g.css';
import '../../css/e/em-82ubin.css';
import '../../css/y/y0o4vtbls.css';
import '../../css/s/sno1kmbxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cg7x8js6g"/><path class="em-82ubin"/><path clip-rule="evenodd" class="y0o4vtbls"/><path clip-rule="evenodd" class="sno1kmbxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:airbuds-check-bold" {...props}></Icon>
