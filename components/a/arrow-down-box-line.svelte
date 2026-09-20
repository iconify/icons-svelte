<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/npgdh3aap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="npgdh3aap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:arrow-down-box-line" {...props}></Icon>
