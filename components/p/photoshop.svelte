<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/okh68-bde.css';
import '../../css/c/cagb5gb_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="okh68-bde"/><path class="cagb5gb_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:photoshop" {...props}></Icon>
