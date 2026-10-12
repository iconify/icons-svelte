<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/b9u5g0bja.css';
import '../../css/s/sigei6ulc.css';
import '../../css/a/a09196i_r.css';
import '../../css/z/ze35a9bxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="b9u5g0bja"/><path class="sigei6ulc"/><path class="a09196i_r"/><path class="ze35a9bxf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:mail-search-duotone" {...props}></Icon>
