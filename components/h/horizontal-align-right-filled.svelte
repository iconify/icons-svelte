<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_j4mhb6r.css';
import '../../css/m/m_f_sobnp.css';
import '../../css/y/yi_zyo09o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a_j4mhb6r"/><rect class="m_f_sobnp"/><rect class="yi_zyo09o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:horizontal-align-right-filled" {...props}></Icon>
