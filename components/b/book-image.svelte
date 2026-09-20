<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/o/o_zfirn9i.css';
import '../../css/o/ot8yzyb7e.css';
import '../../css/y/yoyle7z3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="o_zfirn9i"/><path class="ot8yzyb7e"/><circle class="yoyle7z3v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:book-image" {...props}></Icon>
