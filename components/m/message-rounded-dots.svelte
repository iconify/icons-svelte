<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lk2oa9bac.css';
import '../../css/m/m_i62lbim.css';
import '../../css/b/bhnv2njoo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="lk2oa9bac"/><circle class="m_i62lbim"/><path class="bhnv2njoo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:message-rounded-dots" {...props}></Icon>
