<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a17etlsmp.css';
import '../../css/g/g015acbcu.css';
import '../../css/m/mnelrmb_n.css';
import '../../css/w/wcp-8_b0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a17etlsmp"/><path clip-rule="evenodd" class="g015acbcu"/><path clip-rule="evenodd" class="mnelrmb_n"/><path clip-rule="evenodd" class="wcp-8_b0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:git-fork-bold-duotone" {...props}></Icon>
