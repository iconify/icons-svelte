<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zwofws6qq.css';
import '../../css/v/vu6dscm0p.css';
import '../../css/a/acyzzjbyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zwofws6qq"/><path class="vu6dscm0p"/><path class="acyzzjbyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:dog" {...props}></Icon>
