<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k17b-1bez.css';
import '../../css/f/flaiagb5f.css';
import '../../css/p/pknpwpb5q.css';
import '../../css/b/bpo0h2box.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k17b-1bez"/><path class="flaiagb5f"/><path class="pknpwpb5q"/><path class="bpo0h2box"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:house-user" {...props}></Icon>
