<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iymf6qb3j.css';
import '../../css/v/v5xrdcb0l.css';
import '../../css/q/qnd7fcbei.css';
import '../../css/n/nnp21bc0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iymf6qb3j wm-k"/><path class="v5xrdcb0l wm-k"/><path class="qnd7fcbei wm-k"/><path class="nnp21bc0o wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:mouse" {...props}></Icon>
