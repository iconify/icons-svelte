<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bak9k5bed.css';
import '../../css/t/titlh42pv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bak9k5bed"/><path clip-rule="evenodd" class="titlh42pv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:explicit-outline" {...props}></Icon>
