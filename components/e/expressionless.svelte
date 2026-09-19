<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gshe_di8n.css';
import '../../css/v/vpfegd3_c.css';
import '../../css/s/s18lac6xp.css';
import '../../css/d/dispmjy6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gshe_di8n"/><path class="vpfegd3_c"/><path class="s18lac6xp"/><path class="dispmjy6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:expressionless" {...props}></Icon>
