<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/riomwtb3m.css';
import '../../css/x/xcwrauxib.css';
import '../../css/l/ltwci7nut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="riomwtb3m"/><path class="xcwrauxib"/><path class="ltwci7nut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:planets" {...props}></Icon>
