<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kd99cys7x.css';
import '../../css/y/y00wue9pd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kd99cys7x"/><path class="y00wue9pd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:plane-2-bold" {...props}></Icon>
