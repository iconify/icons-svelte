<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/g/g74vzqvdz.css';
import '../../css/v/vselo_bxr.css';
import '../../css/a/ang81xbkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="g74vzqvdz"/><path class="vselo_bxr"/><path class="ang81xbkn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:desktop-action-monitor-edit" {...props}></Icon>
