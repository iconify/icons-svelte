<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rix0hrcrg.css';
import '../../css/z/ztrntccql.css';
import '../../css/e/ejq36vvzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rix0hrcrg wm-k"/><path class="wm-a ztrntccql"/><path class="ejq36vvzq wm-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:file-image" {...props}></Icon>
