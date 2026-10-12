<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ind2jwvlw.css';
import '../../css/v/vdxd2qb6h.css';
import '../../css/u/u3ebn3b7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ind2jwvlw"/><path class="vdxd2qb6h"/><path class="u3ebn3b7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:book-up-2-filled" {...props}></Icon>
