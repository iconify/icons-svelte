<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twz5xh3ue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="twz5xh3ue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:lock-24" {...props}></Icon>
