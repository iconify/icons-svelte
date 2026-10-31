<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/l/ljk6fpbmg.css';
import '../../css/g/g55v74fib.css';
import '../../css/c/caum75byk.css';
import '../../css/i/i5itnzzkz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="ljk6fpbmg wm-shadow"/><path class="g55v74fib wm-shadow"/><path class="caum75byk"/><path class="i5itnzzkz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:panel-top" {...props}></Icon>
