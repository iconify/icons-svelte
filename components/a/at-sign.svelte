<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/or0-msbfm.css';
import '../../css/q/qtdly1ban.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="or0-msbfm"/><path class="qtdly1ban"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:at-sign" {...props}></Icon>
