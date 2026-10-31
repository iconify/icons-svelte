<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/n/n-7cw7b1t.css';
import '../../css/p/pau5b2f0a.css';
import '../../css/z/zbp8r9b5n.css';
import '../../css/c/cvzi6sbks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="n-7cw7b1t wm-shadow"/><path class="pau5b2f0a wm-shadow"/><path class="zbp8r9b5n"/><path class="cvzi6sbks"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:gingerbread-man" {...props}></Icon>
