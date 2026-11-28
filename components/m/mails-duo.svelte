<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twofskbvn.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/u/ukdpmtbhl.css';
import '../../css/p/p-gxi9bkc.css';
import '../../css/n/ntl4se4mo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary twofskbvn"/><g class="dt0cm9dhy primary"><path class="ukdpmtbhl"/><path class="p-gxi9bkc"/><path class="ntl4se4mo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:mails-duo" {...props}></Icon>
