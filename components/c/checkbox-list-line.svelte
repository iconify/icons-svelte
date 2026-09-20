<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/h/hnsc5ccym.css';
import '../../css/g/g7z1o33yi.css';
import '../../css/q/q_kfvnbxk.css';
import '../../css/g/grp9m_10s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hnsc5ccym"/><rect class="g7z1o33yi"/><rect class="q_kfvnbxk"/><rect class="grp9m_10s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:checkbox-list-line" {...props}></Icon>
