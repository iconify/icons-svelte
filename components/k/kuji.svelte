<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w3m48pb3x.css';
import '../../css/t/tcklekb-k.css';
import '../../css/f/fr78w7boo.css';
import '../../css/j/j4gjthbnr.css';
import '../../css/t/tatq48slt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w3m48pb3x"/><path class="tcklekb-k"/><path class="fr78w7boo"/><path class="j4gjthbnr"/><path class="tatq48slt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:kuji" {...props}></Icon>
