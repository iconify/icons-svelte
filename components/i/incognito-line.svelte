<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/x/xkf6ttbje.css';
import '../../css/a/a96k7rbus.css';
import '../../css/c/ceitnjb9j.css';
import '../../css/w/wy2n5sbyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xkf6ttbje"/><circle class="a96k7rbus"/><circle class="ceitnjb9j"/><path class="wy2n5sbyh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:incognito-line" {...props}></Icon>
