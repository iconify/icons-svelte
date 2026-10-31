<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wrscgzb-f.css';
import '../../css/s/st6uysbjd.css';
import '../../css/a/a-wwm5bze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="wrscgzb-f"/><path class="st6uysbjd"/><path class="a-wwm5bze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:north-korea" {...props}></Icon>
