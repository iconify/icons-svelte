<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k75pbxo-h.css';
import '../../css/o/owfk9nbdh.css';
import '../../css/i/iqy1ivbzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k75pbxo-h wm-k"/><path class="owfk9nbdh wm-a"/><path class="iqy1ivbzl wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:percent" {...props}></Icon>
