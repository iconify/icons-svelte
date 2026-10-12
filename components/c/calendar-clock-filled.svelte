<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wo3fevbda.css';
import '../../css/g/gz7nuqwbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wo3fevbda"/><path class="gz7nuqwbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:calendar-clock-filled" {...props}></Icon>
