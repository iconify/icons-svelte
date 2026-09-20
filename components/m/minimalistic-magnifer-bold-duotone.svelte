<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-tqdrbyb.css';
import '../../css/j/j-tmtc6ls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g-tqdrbyb"/><path clip-rule="evenodd" class="j-tmtc6ls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:minimalistic-magnifer-bold-duotone" {...props}></Icon>
