<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sijq6ibko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sijq6ibko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:badge-japanese-yen-filled" {...props}></Icon>
