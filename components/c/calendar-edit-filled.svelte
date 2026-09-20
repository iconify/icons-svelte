<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/biyv__4lr.css';
import '../../css/f/f_fvtdbvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="biyv__4lr"/><path class="f_fvtdbvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:calendar-edit-filled" {...props}></Icon>
