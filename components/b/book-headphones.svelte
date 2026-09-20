<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/o/ot8yzyb7e.css';
import '../../css/s/sgy0oab2v.css';
import '../../css/w/w6g5yhqkl.css';
import '../../css/i/inewx5b5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ot8yzyb7e"/><path class="sgy0oab2v"/><circle class="w6g5yhqkl"/><circle class="inewx5b5l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:book-headphones" {...props}></Icon>
