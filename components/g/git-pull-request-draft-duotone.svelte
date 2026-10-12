<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/euxpybc-u.css';
import '../../css/z/zcl772bhd.css';
import '../../css/y/yr_f-qwns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="euxpybc-u"/><path class="zcl772bhd"/><path class="yr_f-qwns"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:git-pull-request-draft-duotone" {...props}></Icon>
