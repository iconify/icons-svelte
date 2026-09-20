<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lua9-g0jf.css';
import '../../css/d/dsjuhdb_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lua9-g0jf"/><path class="dsjuhdb_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:emp" {...props}></Icon>
