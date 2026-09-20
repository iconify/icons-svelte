<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/n/nvjgaobrz.css';
import '../../css/z/zcrcylsxu.css';
import '../../css/w/w65t7vpsn.css';
import '../../css/i/ien-av9-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><circle class="nvjgaobrz"/><circle class="zcrcylsxu"/><circle class="w65t7vpsn"/><path class="ien-av9-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:git-fork" {...props}></Icon>
